<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrxj1v2xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jrxj1v2xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:g-u-i-d" {...props}></Icon>
