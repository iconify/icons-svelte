<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uilm590_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uilm590_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-program-filled" {...props}></Icon>
