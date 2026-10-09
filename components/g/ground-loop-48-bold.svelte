<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbgn9e5js.css';
import '../../css/t/tjum5_rgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nbgn9e5js"/><path class="tjum5_rgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-loop-48-bold" {...props}></Icon>
