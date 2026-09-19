<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zugda47zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zugda47zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:glide" {...props}></Icon>
