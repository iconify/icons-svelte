<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip6mpoouv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ip6mpoouv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hourglass-start" {...props}></Icon>
