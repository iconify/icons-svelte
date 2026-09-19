<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo6n4nbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo6n4nbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:palm" {...props}></Icon>
