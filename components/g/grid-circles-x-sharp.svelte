<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyc8fwb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyc8fwb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-circles-x-sharp" {...props}></Icon>
