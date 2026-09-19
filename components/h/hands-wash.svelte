<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr1u8et0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pr1u8et0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hands-wash" {...props}></Icon>
