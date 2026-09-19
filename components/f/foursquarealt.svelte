<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1_o64lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="jv1_o64lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:foursquarealt" {...props}></Icon>
