<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxfb3xbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfb3xbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-zap-solid" {...props}></Icon>
