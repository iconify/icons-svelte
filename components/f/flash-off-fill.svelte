<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laq_aqbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laq_aqbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:flash-off-fill" {...props}></Icon>
