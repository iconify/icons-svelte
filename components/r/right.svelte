<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6-exhbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":475,"height":717};
const content = `<path class="n6-exhbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:right" {...props}></Icon>
