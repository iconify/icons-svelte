<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbjf8_boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dbjf8_boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cake" {...props}></Icon>
