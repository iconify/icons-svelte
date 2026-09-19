<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-4jobclo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n-4jobclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:funnel-plot-outlined" {...props}></Icon>
