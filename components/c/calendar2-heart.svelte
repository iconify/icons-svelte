<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te1x5e53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="te1x5e53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-heart" {...props}></Icon>
