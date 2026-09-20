<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw1d0pbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mw1d0pbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chess-knight" {...props}></Icon>
