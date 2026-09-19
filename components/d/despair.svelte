<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cisyq9bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cisyq9bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:despair" {...props}></Icon>
