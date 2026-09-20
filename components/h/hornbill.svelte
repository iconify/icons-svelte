<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sod9htjhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sod9htjhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hornbill" {...props}></Icon>
