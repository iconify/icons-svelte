<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux1cfnjeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ux1cfnjeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:blind" {...props}></Icon>
