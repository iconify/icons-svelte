<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg84oub9d.css';
import '../../css/u/udvwo6blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mg84oub9d"/><path clip-rule="evenodd" class="udvwo6blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:anja-solid" {...props}></Icon>
