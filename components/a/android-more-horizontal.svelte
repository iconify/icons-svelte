<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3_o6v0vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3_o6v0vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-more-horizontal" {...props}></Icon>
