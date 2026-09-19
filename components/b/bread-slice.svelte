<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj2_z7fcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fj2_z7fcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bread-slice" {...props}></Icon>
