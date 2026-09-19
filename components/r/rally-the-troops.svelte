<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8e47hb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8e47hb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rally-the-troops" {...props}></Icon>
