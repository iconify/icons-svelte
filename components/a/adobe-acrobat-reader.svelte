<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-gonbb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w-gonbb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-acrobat-reader" {...props}></Icon>
