<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp4y0ebkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4y0ebkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-calling-filled" {...props}></Icon>
