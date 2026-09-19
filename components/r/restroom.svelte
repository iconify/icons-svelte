<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2rti4btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h2rti4btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:restroom" {...props}></Icon>
