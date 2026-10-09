<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tex_f1bsd.css';
import '../../css/q/q4u-icn5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tex_f1bsd"/><path class="q4u-icn5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-down-20-bold" {...props}></Icon>
