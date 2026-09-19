<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baes3_9xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="baes3_9xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brass-eye" {...props}></Icon>
