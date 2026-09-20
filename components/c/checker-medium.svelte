<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgk369bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wgk369bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checker-medium" {...props}></Icon>
