<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo4o7cler.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vo4o7cler"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:interdiction" {...props}></Icon>
