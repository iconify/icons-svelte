<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5g-ccfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv5g-ccfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pause" {...props}></Icon>
