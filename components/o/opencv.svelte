<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwhruq8yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwhruq8yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:opencv" {...props}></Icon>
