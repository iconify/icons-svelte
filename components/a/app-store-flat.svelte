<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6_bgxfso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i6_bgxfso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:app-store-flat" {...props}></Icon>
