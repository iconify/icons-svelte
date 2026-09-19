<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4k29qbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4k29qbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:jet-fighter-up" {...props}></Icon>
