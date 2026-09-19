<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5l8xbcpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5l8xbcpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:rectangle-stack" {...props}></Icon>
