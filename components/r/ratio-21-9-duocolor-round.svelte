<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihwhwwz8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihwhwwz8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-21-9-duocolor-round" {...props}></Icon>
