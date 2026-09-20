<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x990d3bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x990d3bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-text-filled" {...props}></Icon>
