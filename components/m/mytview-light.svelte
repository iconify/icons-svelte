<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzhc7cblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vzhc7cblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mytview-light" {...props}></Icon>
