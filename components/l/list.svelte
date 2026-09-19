<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tawv9dyxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tawv9dyxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:list" {...props}></Icon>
