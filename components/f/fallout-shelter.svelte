<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzy_64bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dzy_64bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fallout-shelter" {...props}></Icon>
