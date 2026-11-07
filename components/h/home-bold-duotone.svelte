<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jglmwo91y.css';
import '../../css/f/fpavm-beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jglmwo91y"/><path class="fpavm-beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-bold-duotone" {...props}></Icon>
