<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3_3wsb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f3_3wsb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:font-increase" {...props}></Icon>
