<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0bz1cnyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0bz1cnyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pitchfork" {...props}></Icon>
