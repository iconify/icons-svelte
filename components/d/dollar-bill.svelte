<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyoonebhp.css';
import '../../css/i/i7yk66pmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xyoonebhp"/><path class="i7yk66pmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:dollar-bill" {...props}></Icon>
