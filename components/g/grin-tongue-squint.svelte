<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqbnbtbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="dqbnbtbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-tongue-squint" {...props}></Icon>
