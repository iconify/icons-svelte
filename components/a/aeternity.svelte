<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg6mo1bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg6mo1bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:aeternity" {...props}></Icon>
