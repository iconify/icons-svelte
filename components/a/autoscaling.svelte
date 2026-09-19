<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5qpf5bjd.css';
import '../../css/s/stdjlnzrk.css';
import '../../css/g/gxdbe2bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e5qpf5bjd"/><path class="stdjlnzrk"/><path class="gxdbe2bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:autoscaling" {...props}></Icon>
