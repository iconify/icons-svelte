<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-ik06-dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-ik06-dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hourglass-cog" {...props}></Icon>
