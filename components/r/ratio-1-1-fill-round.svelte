<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llwohje9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llwohje9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-1-1-fill-round" {...props}></Icon>
