<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj264cgmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vj264cgmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-filled" {...props}></Icon>
