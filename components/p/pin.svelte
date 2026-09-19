<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/benc_65rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":426,"height":768};
const content = `<path class="benc_65rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pin" {...props}></Icon>
