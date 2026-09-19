<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5k7lbbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5k7lbbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-007" {...props}></Icon>
