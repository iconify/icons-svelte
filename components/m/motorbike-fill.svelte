<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlyu3-1bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlyu3-1bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:motorbike-fill" {...props}></Icon>
