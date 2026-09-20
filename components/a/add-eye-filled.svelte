<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc2yc2txt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uc2yc2txt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-eye-filled" {...props}></Icon>
