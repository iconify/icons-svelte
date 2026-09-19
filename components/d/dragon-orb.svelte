<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4f8q8qqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j4f8q8qqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dragon-orb" {...props}></Icon>
