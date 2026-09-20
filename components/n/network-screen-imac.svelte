<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsxpagbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsxpagbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:network-screen-imac" {...props}></Icon>
