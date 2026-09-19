<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ooki_9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i9ooki_9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flower-hat" {...props}></Icon>
