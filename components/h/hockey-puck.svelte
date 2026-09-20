<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc42u29hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tc42u29hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hockey-puck" {...props}></Icon>
