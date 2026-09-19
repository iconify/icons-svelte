<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgbah0bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zgbah0bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:kickstarter-k" {...props}></Icon>
