<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlepf_eml.css';
import '../../css/q/qbsvsyi4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nlepf_eml"/><path class="qbsvsyi4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:pie-chart" {...props}></Icon>
