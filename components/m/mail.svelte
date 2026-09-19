<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt3e4cb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yt3e4cb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mail" {...props}></Icon>
