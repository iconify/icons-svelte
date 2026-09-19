<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5592g8sw.css';
import '../../css/p/pemo8gb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5592g8sw"/><path class="pemo8gb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-man" {...props}></Icon>
