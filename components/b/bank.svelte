<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg4sf4mbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fg4sf4mbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bank" {...props}></Icon>
