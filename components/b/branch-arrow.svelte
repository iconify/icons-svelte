<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvjdxgl3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvjdxgl3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:branch-arrow" {...props}></Icon>
