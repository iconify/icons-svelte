<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f73t0tbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f73t0tbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:megaphone-alert" {...props}></Icon>
