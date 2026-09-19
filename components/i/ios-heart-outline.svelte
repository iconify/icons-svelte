<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd9f0ccnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd9f0ccnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-heart-outline" {...props}></Icon>
