<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/torkgl_uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="torkgl_uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-20-bold" {...props}></Icon>
