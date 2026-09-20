<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub9rt9blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ub9rt9blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:cloudy" {...props}></Icon>
