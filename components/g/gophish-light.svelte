<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3r9d2zij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3r9d2zij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gophish-light" {...props}></Icon>
