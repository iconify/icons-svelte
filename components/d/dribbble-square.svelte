<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_5p1hkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hj_5p1hkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:dribbble-square" {...props}></Icon>
