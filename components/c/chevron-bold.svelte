<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t40t0mbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t40t0mbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chevron-bold" {...props}></Icon>
