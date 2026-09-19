<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4_ippc5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4_ippc5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-sun" {...props}></Icon>
