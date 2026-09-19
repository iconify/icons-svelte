<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm37cybfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm37cybfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bordered-shield" {...props}></Icon>
