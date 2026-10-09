<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuo0z1gmg.css';
import '../../css/h/hk7ioiexi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cuo0z1gmg"/><path class="hk7ioiexi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glasses-20-bold" {...props}></Icon>
