<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hou_otb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hou_otb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:brand-apple" {...props}></Icon>
