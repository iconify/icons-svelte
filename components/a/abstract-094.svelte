<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw7et_bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw7et_bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-094" {...props}></Icon>
