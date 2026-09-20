<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izsi4qxaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="izsi4qxaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-holding-solid" {...props}></Icon>
