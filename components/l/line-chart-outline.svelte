<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-hzbsqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="si-hzbsqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:line-chart-outline" {...props}></Icon>
