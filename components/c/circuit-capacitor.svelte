<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmq9ty05e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmq9ty05e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-capacitor" {...props}></Icon>
