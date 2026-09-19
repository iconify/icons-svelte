<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/max5n0b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="max5n0b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-turn-to-dots" {...props}></Icon>
