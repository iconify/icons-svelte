<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruhveebsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruhveebsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-trending-down-fill" {...props}></Icon>
