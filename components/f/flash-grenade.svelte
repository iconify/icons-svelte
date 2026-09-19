<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ybwzbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9ybwzbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flash-grenade" {...props}></Icon>
