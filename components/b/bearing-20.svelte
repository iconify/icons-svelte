<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4bjo-bjt.css';
import '../../css/t/tiuaiabal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r4bjo-bjt"/><path class="tiuaiabal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bearing-20" {...props}></Icon>
