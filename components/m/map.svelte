<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_r8p65rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="d_r8p65rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:map" {...props}></Icon>
