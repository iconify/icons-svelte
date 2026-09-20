<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuaqt_rtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuaqt_rtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:et" {...props}></Icon>
