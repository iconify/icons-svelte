<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4cx0b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="sh4cx0b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cloud-disconnect" {...props}></Icon>
