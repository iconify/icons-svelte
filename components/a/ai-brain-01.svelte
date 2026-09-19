<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc4n74b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc4n74b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-brain-01" {...props}></Icon>
