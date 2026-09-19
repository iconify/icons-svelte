<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou22gibla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ou22gibla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fruit-tree" {...props}></Icon>
