<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa3p8cgmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa3p8cgmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-big-up-sharp" {...props}></Icon>
