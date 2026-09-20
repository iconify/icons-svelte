<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vab42o9le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vab42o9le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pterodactyl" {...props}></Icon>
