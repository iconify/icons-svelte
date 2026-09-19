<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrebgjc0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jrebgjc0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:energy-report" {...props}></Icon>
