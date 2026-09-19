<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odo1irb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odo1irb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ping-pong-bat" {...props}></Icon>
