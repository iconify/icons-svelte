<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrzxxobiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wrzxxobiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hryvnia-solid" {...props}></Icon>
