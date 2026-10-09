<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aem9n2zvr.css';
import '../../css/w/wqxi-7byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aem9n2zvr"/><path class="wqxi-7byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-combo-20" {...props}></Icon>
