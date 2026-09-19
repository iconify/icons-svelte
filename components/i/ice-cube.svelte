<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq6c9lvbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq6c9lvbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-cube" {...props}></Icon>
