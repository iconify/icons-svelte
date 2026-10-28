<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s33hyzb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s33hyzb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-to-dot" {...props}></Icon>
