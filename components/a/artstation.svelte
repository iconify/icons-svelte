<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk3xqxb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk3xqxb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:artstation" {...props}></Icon>
