<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk980mb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nk980mb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fish-cooked" {...props}></Icon>
