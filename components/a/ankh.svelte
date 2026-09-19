<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm5z_rb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="vm5z_rb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ankh" {...props}></Icon>
