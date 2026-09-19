<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-41hqbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-41hqbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:camargue-cross" {...props}></Icon>
