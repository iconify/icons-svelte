<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crrcsp6jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="crrcsp6jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excalidraw-dark" {...props}></Icon>
