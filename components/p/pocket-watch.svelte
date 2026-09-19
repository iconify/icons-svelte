<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6wak7bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6wak7bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pocket-watch" {...props}></Icon>
