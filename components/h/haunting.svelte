<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q08fztv6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q08fztv6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:haunting" {...props}></Icon>
