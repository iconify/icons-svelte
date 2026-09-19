<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav5dg_xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jav5dg_xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:laraveljetstream" {...props}></Icon>
