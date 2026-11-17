<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c49mhrr1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c49mhrr1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-from-axis-dashed-vertical" {...props}></Icon>
