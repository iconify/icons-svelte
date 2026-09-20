<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md0h0dbps.css';
import '../../css/l/loqdhccef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="md0h0dbps"/><path class="loqdhccef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-constuction" {...props}></Icon>
