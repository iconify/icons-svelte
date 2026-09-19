<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izjfx1-et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="izjfx1-et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-facebook" {...props}></Icon>
