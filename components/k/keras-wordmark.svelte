<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_flxzbbv.css';
import '../../css/c/c4k71-bhq.css';
import '../../css/i/iovi16bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q_flxzbbv"/><path class="c4k71-bhq"/><path class="iovi16bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:keras-wordmark" {...props}></Icon>
