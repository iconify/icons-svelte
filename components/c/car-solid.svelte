<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb6h6wkcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb6h6wkcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:car-solid" {...props}></Icon>
