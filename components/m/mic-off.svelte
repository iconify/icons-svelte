<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js103e65u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":512};
const content = `<path class="js103e65u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:mic-off" {...props}></Icon>
