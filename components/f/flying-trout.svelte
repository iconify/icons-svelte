<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp37l5bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yp37l5bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flying-trout" {...props}></Icon>
