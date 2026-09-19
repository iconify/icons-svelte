<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_o5xl9_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_o5xl9_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bloody-stash" {...props}></Icon>
