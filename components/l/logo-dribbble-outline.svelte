<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx1b7jeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="btx1b7jeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-dribbble-outline" {...props}></Icon>
