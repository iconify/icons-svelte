<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrrdj-bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vrrdj-bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:course" {...props}></Icon>
