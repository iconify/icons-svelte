<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7kyzlbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kyzlbcb wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mail-open-solid" {...props}></Icon>
