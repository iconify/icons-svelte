<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_s6b-ete.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i_s6b-ete"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:berries-bowl" {...props}></Icon>
