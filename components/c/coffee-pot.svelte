<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv3g54blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv3g54blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coffee-pot" {...props}></Icon>
