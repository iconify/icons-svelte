<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk59f9vxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jk59f9vxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diamond-trophy" {...props}></Icon>
