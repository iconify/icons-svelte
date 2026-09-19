<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htd5qgbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htd5qgbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:american-football-ball" {...props}></Icon>
