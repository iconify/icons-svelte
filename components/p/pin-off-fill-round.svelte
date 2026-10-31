<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5k55sb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5k55sb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pin-off-fill-round" {...props}></Icon>
