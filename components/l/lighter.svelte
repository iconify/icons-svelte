<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo0zxtj6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uo0zxtj6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lighter" {...props}></Icon>
