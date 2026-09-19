<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnw_ebvht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wnw_ebvht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:booze" {...props}></Icon>
