<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_d-36btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_d-36btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:process-fill" {...props}></Icon>
