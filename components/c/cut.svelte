<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3hvzhb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p3hvzhb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cut" {...props}></Icon>
