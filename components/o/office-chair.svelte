<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9k5d7bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9k5d7bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:office-chair" {...props}></Icon>
