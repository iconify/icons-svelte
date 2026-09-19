<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpenvzb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpenvzb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:laser-gun" {...props}></Icon>
