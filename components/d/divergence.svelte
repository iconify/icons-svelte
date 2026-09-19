<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or7x6dsdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or7x6dsdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:divergence" {...props}></Icon>
