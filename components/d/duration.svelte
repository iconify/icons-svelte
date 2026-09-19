<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl9kmyrwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl9kmyrwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:duration" {...props}></Icon>
