<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvay3xbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvay3xbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reply" {...props}></Icon>
