<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjvt0lfrb.css';
import '../../css/n/nu2_-nbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hjvt0lfrb"/><path class="nu2_-nbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-heart" {...props}></Icon>
