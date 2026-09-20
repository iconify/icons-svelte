<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i23k0-8ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i23k0-8ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:noentry" {...props}></Icon>
