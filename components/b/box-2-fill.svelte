<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd3_teb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd3_teb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:box-2-fill" {...props}></Icon>
