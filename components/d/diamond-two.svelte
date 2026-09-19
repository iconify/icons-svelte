<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oekb3_2rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oekb3_2rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:diamond-two" {...props}></Icon>
