<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuaqtw_ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="cuaqtw_ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pump-medical" {...props}></Icon>
