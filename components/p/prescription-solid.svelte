<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocjhggbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ocjhggbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:prescription-solid" {...props}></Icon>
