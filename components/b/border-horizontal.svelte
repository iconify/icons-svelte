<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm8holt9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jm8holt9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:border-horizontal" {...props}></Icon>
