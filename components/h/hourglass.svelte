<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_sombtl.css';
import '../../css/c/cpua5hbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nc_sombtl"/><path class="cpua5hbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hourglass" {...props}></Icon>
