<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvncfgbpp.css';
import '../../css/r/roohfabdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvncfgbpp"/><path class="roohfabdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-check-corner-filled" {...props}></Icon>
