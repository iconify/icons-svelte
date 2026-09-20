<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izecqj6hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="izecqj6hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:behance" {...props}></Icon>
