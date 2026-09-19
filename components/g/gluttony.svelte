<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moq0sj2-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="moq0sj2-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gluttony" {...props}></Icon>
