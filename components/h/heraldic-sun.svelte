<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt4ee93ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4ee93ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heraldic-sun" {...props}></Icon>
