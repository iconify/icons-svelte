<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-g_hzbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c-g_hzbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rancher" {...props}></Icon>
