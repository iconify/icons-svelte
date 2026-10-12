<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4nvvob8l.css';
import '../../css/d/dcy-hxbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c4nvvob8l"/><path class="dcy-hxbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:duplicate-stroke-20" {...props}></Icon>
