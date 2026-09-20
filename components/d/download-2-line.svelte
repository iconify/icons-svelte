<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3s_jfmpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3s_jfmpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-2-line" {...props}></Icon>
