<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxil73bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxil73bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:printer-line" {...props}></Icon>
