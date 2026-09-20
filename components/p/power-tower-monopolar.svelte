<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm5kf3b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xm5kf3b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-monopolar" {...props}></Icon>
