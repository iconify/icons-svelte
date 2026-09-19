<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-4yw3brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-4yw3brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:radar-dish" {...props}></Icon>
