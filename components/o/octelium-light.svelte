<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6def11eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t6def11eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octelium-light" {...props}></Icon>
