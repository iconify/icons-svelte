<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imo-0w39a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="imo-0w39a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bar-chart-line-fill" {...props}></Icon>
