<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq6gnbbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qq6gnbbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gem-pendant" {...props}></Icon>
