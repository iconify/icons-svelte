<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4mf6cdoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4mf6cdoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-7-hearts" {...props}></Icon>
