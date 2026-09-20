<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws1ovebla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws1ovebla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:link-broken-1" {...props}></Icon>
