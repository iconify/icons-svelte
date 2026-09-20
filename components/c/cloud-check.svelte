<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8lvwbib.css';
import '../../css/c/ccpdzcc_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="ccpdzcc_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-check" {...props}></Icon>
