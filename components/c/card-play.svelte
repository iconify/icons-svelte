<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ermx9q4nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ermx9q4nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-play" {...props}></Icon>
