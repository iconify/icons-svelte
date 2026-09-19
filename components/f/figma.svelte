<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uug-36bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="uug-36bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:figma" {...props}></Icon>
