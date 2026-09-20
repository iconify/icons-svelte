<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihud3xmus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihud3xmus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-filled" {...props}></Icon>
