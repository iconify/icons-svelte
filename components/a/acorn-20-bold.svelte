<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gozz3nbxj.css';
import '../../css/m/mwkd_0bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gozz3nbxj"/><path class="mwkd_0bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acorn-20-bold" {...props}></Icon>
