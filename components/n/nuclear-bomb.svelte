<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqv43tb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqv43tb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nuclear-bomb" {...props}></Icon>
