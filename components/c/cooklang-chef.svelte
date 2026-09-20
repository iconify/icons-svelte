<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j99-dtc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j99-dtc4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cooklang-chef" {...props}></Icon>
