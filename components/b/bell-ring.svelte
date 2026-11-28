<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir8b8ublh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir8b8ublh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bell-ring" {...props}></Icon>
