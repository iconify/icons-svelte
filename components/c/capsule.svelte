<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0-zhsb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0-zhsb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:capsule" {...props}></Icon>
