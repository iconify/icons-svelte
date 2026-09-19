<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzggoov-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pzggoov-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-medical-circle-xmark" {...props}></Icon>
