<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0ysjab1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u0ysjab1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-amazon-pay" {...props}></Icon>
