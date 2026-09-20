<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i52g8qbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i52g8qbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-z-filled" {...props}></Icon>
