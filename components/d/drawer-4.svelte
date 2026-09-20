<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcq8hnbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcq8hnbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:drawer-4" {...props}></Icon>
