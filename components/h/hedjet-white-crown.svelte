<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-j-sbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu-j-sbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hedjet-white-crown" {...props}></Icon>
