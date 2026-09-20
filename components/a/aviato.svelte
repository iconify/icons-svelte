<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btpkolbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="btpkolbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:aviato" {...props}></Icon>
