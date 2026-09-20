<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inq4aqb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="inq4aqb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:drum-solid" {...props}></Icon>
