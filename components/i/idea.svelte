<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdxce3pve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vdxce3pve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:idea" {...props}></Icon>
