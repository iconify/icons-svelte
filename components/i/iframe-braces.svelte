<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrmg1583g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrmg1583g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-braces" {...props}></Icon>
