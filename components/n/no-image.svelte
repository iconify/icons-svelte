<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5kjf9bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5kjf9bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:no-image" {...props}></Icon>
