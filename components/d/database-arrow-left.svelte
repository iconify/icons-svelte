<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtkvy1_xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vtkvy1_xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:database-arrow-left" {...props}></Icon>
