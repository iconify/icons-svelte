<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5sx-kk8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d5sx-kk8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:line-chart" {...props}></Icon>
