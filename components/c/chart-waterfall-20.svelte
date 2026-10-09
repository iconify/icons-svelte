<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aem9n2zvr.css';
import '../../css/u/ubsqc0zyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aem9n2zvr"/><path class="ubsqc0zyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-waterfall-20" {...props}></Icon>
