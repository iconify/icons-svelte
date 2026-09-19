<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki_r4_mpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ki_r4_mpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-booth" {...props}></Icon>
