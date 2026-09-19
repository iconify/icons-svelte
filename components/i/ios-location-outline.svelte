<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs68a2a3q.css';
import '../../css/c/cb56blb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gs68a2a3q"/><path class="cb56blb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-location-outline" {...props}></Icon>
