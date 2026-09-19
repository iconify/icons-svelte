<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxuxtu9xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxuxtu9xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fluffy-swirl" {...props}></Icon>
