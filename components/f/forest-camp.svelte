<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9dvr0bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9dvr0bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:forest-camp" {...props}></Icon>
