<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdp_mqutl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdp_mqutl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-indeterminate-line" {...props}></Icon>
