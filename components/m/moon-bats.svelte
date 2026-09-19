<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjr5vrb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjr5vrb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:moon-bats" {...props}></Icon>
