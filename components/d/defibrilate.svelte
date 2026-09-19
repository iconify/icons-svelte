<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arz71r5ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arz71r5ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:defibrilate" {...props}></Icon>
