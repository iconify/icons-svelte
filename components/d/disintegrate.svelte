<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p93ebq0sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p93ebq0sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:disintegrate" {...props}></Icon>
