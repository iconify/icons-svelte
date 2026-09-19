<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yupvxm31u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="yupvxm31u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:keyboard-hide" {...props}></Icon>
