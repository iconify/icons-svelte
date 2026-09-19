<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkcgv_1ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkcgv_1ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:new-shoot" {...props}></Icon>
