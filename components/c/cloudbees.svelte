<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek5vy5bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ek5vy5bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cloudbees" {...props}></Icon>
