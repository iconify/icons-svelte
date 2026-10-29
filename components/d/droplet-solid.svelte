<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymhvrff1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k ymhvrff1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplet-solid" {...props}></Icon>
