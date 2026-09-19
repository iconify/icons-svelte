<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4pc4b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yt4pc4b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:deezer" {...props}></Icon>
