<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gegu87b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gegu87b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:line-chart" {...props}></Icon>
