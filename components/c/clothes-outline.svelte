<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx740u_sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx740u_sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:clothes-outline" {...props}></Icon>
