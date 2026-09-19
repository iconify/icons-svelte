<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w94jr_bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w94jr_bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:missile-launcher" {...props}></Icon>
