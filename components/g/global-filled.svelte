<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx93x9b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx93x9b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:global-filled" {...props}></Icon>
