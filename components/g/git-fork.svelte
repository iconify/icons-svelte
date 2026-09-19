<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz5z4w1dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2560,"height":2048};
const content = `<path class="fz5z4w1dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:git-fork" {...props}></Icon>
