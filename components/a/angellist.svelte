<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7tep0bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u7tep0bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angellist" {...props}></Icon>
