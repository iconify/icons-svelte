<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1kbdi40r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="m1kbdi40r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:celsius" {...props}></Icon>
