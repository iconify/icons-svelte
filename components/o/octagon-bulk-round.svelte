<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_joi3_le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_joi3_le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-bulk-round" {...props}></Icon>
