<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwjh3lyto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwjh3lyto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:biohazard" {...props}></Icon>
