<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_m1xb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pk_m1xb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:deviantart" {...props}></Icon>
