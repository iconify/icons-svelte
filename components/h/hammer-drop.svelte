<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl14hb56d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jl14hb56d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hammer-drop" {...props}></Icon>
