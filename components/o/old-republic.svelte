<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4wplvplu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w4wplvplu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:old-republic" {...props}></Icon>
