<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxd2pgb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxd2pgb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lunar-wand" {...props}></Icon>
