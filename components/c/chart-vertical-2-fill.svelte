<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb5w3nb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb5w3nb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-vertical-2-fill" {...props}></Icon>
