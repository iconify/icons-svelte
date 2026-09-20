<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie9unqupy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie9unqupy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-2-filled" {...props}></Icon>
