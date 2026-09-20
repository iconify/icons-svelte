<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb2gxib2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb2gxib2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chevron-down" {...props}></Icon>
