<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-o7sbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yz-o7sbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pencil" {...props}></Icon>
