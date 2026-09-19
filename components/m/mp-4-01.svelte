<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-o7nbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-o7nbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mp-4-01" {...props}></Icon>
