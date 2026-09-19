<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8v2597ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r8v2597ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:laptop-medical" {...props}></Icon>
