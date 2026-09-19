<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na_o-44vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="na_o-44vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flower-emblem" {...props}></Icon>
