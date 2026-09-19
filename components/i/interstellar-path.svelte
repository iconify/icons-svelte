<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df8ps71ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df8ps71ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:interstellar-path" {...props}></Icon>
