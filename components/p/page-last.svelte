<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkaqti56k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkaqti56k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:page-last" {...props}></Icon>
