<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyv23_bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyv23_bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-5-diamonds" {...props}></Icon>
