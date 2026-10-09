<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcx_6xb7j.css';
import '../../css/w/wzhdi44yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lcx_6xb7j"/><path class="wzhdi44yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bbq-20-bold" {...props}></Icon>
