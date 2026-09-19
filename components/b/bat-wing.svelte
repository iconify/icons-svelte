<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5un4obpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5un4obpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bat-wing" {...props}></Icon>
