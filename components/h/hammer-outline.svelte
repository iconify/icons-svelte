<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo_5wnbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uo_5wnbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hammer-outline" {...props}></Icon>
