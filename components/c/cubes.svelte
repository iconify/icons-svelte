<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlkqiu3ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mlkqiu3ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cubes" {...props}></Icon>
