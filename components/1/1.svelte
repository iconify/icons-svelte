<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2s9xyjfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="f2s9xyjfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:1" {...props}></Icon>
