<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2kiocawz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k2kiocawz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:flow-chart" {...props}></Icon>
