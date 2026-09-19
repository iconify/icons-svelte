<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf_ub3bqf.css';
import '../../css/r/riavwwb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cf_ub3bqf"/><path class="riavwwb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-business-impact-assessment" {...props}></Icon>
