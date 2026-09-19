<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzdvk5bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gzdvk5bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building" {...props}></Icon>
