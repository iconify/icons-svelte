<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe9bmcbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe9bmcbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cassette" {...props}></Icon>
