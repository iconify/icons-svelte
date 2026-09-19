<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp08kkbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp08kkbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frog" {...props}></Icon>
