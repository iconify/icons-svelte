<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p372pobtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p372pobtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:medium" {...props}></Icon>
