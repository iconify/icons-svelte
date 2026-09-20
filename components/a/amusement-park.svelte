<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fduf5bcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fduf5bcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:amusement-park" {...props}></Icon>
