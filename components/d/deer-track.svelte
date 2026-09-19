<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7finsgjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7finsgjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:deer-track" {...props}></Icon>
