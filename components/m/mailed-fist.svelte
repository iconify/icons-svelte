<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6banzb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y6banzb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mailed-fist" {...props}></Icon>
