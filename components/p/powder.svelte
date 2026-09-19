<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocb9_nbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocb9_nbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:powder" {...props}></Icon>
