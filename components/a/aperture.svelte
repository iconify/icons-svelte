<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_x25aclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h_x25aclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:aperture" {...props}></Icon>
