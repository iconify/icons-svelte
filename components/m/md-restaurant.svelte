<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn-6hubiu.css';
import '../../css/w/w59lw5byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn-6hubiu"/><path class="w59lw5byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-restaurant" {...props}></Icon>
