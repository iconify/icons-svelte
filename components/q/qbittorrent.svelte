<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n03l_4bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n03l_4bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qbittorrent" {...props}></Icon>
