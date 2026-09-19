<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf6zrjvvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf6zrjvvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lockpicks" {...props}></Icon>
