<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9eo-ujzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q9eo-ujzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:list-solid" {...props}></Icon>
