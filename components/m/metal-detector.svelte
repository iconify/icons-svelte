<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgw4z_mvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgw4z_mvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:metal-detector" {...props}></Icon>
