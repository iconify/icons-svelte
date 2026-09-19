<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7x4lpb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7x4lpb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:phrygian-cap" {...props}></Icon>
