<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vayrid8hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vayrid8hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-line" {...props}></Icon>
