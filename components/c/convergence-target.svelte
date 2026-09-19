<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf0e2sbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf0e2sbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:convergence-target" {...props}></Icon>
