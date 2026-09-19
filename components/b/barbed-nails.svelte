<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98d_oboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d98d_oboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-nails" {...props}></Icon>
