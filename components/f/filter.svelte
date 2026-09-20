<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx362ib6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cx362ib6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:filter" {...props}></Icon>
