<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4j5yt_zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n4j5yt_zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:key-flat" {...props}></Icon>
