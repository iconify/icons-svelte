<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wllc8hh9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wllc8hh9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-sm-fill-12" {...props}></Icon>
