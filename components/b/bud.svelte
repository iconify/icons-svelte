<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7tltbcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7tltbcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bud" {...props}></Icon>
