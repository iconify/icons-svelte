<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuh421bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vuh421bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bar-chart-vertical-filter-solid" {...props}></Icon>
