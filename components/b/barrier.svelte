<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbr5iv52a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbr5iv52a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barrier" {...props}></Icon>
