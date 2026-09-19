<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm1kpib8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jm1kpib8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fast-forward-button" {...props}></Icon>
