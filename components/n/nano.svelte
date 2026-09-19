<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq-p_uboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lq-p_uboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nano" {...props}></Icon>
