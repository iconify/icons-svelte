<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg9bewbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg9bewbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:floobits" {...props}></Icon>
