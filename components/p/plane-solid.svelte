<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldu42lbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldu42lbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane-solid" {...props}></Icon>
