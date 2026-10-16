<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p16fzd8jz.css';
import '../../css/r/rpdwkt9nl.css';
import '../../css/j/jeyqzjnhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p16fzd8jz"/><path class="rpdwkt9nl"/><path class="jeyqzjnhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-alert-20-bold" {...props}></Icon>
