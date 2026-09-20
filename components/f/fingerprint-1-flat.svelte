<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr9_-zvzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wr9_-zvzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:fingerprint-1-flat" {...props}></Icon>
