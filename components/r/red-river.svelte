<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mki427-cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mki427-cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:red-river" {...props}></Icon>
