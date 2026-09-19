<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcqpgct8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hcqpgct8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-fill-16" {...props}></Icon>
