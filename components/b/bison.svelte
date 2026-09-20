<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndi969tmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ndi969tmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bison" {...props}></Icon>
