<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d96mkv88n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d96mkv88n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:incisors" {...props}></Icon>
