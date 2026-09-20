<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4yhcfbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4yhcfbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-space-between" {...props}></Icon>
