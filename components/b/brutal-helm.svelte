<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nly-8rbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nly-8rbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brutal-helm" {...props}></Icon>
