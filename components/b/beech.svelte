<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf14bmjhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wf14bmjhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beech" {...props}></Icon>
