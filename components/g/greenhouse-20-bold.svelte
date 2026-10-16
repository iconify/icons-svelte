<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h228pmbtq.css';
import '../../css/j/jaad26bbm.css';
import '../../css/k/ky8gx6l8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h228pmbtq"/><path class="jaad26bbm"/><path class="ky8gx6l8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:greenhouse-20-bold" {...props}></Icon>
