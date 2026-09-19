<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkfjl_8-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="rkfjl_8-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:football-ball" {...props}></Icon>
