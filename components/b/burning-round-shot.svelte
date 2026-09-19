<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kscnyxbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kscnyxbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burning-round-shot" {...props}></Icon>
