<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04d5fqwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s04d5fqwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:css3" {...props}></Icon>
