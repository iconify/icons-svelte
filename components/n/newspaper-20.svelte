<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1qjmetax.css';
import '../../css/e/ev3t13bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v1qjmetax"/><path class="ev3t13bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:newspaper-20" {...props}></Icon>
