<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9bw8kbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9bw8kbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:replace-all-filled" {...props}></Icon>
