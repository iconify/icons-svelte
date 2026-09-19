<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyggh3xhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyggh3xhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-up" {...props}></Icon>
