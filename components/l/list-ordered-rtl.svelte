<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm0o978be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm0o978be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:list-ordered-rtl" {...props}></Icon>
