<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obbjn7b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obbjn7b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:film-strip" {...props}></Icon>
