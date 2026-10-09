<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc5w0p7ef.css';
import '../../css/j/jnqm95cmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hc5w0p7ef"/><path class="jnqm95cmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hair-dryer-20-bold" {...props}></Icon>
