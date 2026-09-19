<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd87p4iod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd87p4iod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cooler" {...props}></Icon>
