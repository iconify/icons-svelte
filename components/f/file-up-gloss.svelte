<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb_mgfbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb_mgfbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-up-gloss" {...props}></Icon>
