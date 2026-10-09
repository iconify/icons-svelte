<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jea-yh2jg.css';
import '../../css/d/dxyc4p_3e.css';
import '../../css/q/q73kfvgtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jea-yh2jg"/><path class="dxyc4p_3e"/><path class="q73kfvgtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:package-20-bold" {...props}></Icon>
