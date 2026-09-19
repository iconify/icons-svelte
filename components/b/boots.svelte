<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouulk7_aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ouulk7_aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boots" {...props}></Icon>
