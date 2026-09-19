<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfv_i_5tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfv_i_5tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-098" {...props}></Icon>
