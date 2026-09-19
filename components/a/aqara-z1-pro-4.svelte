<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z51nb4bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z51nb4bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-z1-pro-4" {...props}></Icon>
