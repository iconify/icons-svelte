<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo6qorwfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="oo6qorwfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hurricane" {...props}></Icon>
