<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-sm-zscq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-sm-zscq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lighthouse" {...props}></Icon>
