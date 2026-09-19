<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzkpz1bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="fzkpz1bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-holding-medical" {...props}></Icon>
