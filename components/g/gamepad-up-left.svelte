<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fauv83bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fauv83bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-up-left" {...props}></Icon>
