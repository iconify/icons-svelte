<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wextjnb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wextjnb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clover" {...props}></Icon>
