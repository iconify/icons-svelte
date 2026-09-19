<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cajxjqbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cajxjqbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:charging-station-filled" {...props}></Icon>
