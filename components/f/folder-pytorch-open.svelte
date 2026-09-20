<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4bb7ybtz.css';
import '../../css/x/xns9x_bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f4bb7ybtz"/><path class="xns9x_bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pytorch-open" {...props}></Icon>
