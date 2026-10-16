<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdest5b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdest5b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-mix-20-bold" {...props}></Icon>
