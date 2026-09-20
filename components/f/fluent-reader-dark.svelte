<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6bzm23k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg6bzm23k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluent-reader-dark" {...props}></Icon>
