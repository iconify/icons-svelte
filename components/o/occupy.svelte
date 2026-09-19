<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro2c__2kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ro2c__2kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:occupy" {...props}></Icon>
