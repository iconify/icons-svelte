<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb-ee9b3j.css';
import '../../css/r/rkamcyd2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-ee9b3j"/><path class="rkamcyd2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-right-square" {...props}></Icon>
