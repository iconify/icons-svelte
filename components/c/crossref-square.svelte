<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihhsa8u5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ihhsa8u5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:crossref-square" {...props}></Icon>
