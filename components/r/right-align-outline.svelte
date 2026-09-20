<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq2klur4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kq2klur4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:right-align-outline" {...props}></Icon>
