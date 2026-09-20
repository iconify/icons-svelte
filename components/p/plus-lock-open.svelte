<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdtkkuksl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdtkkuksl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-lock-open" {...props}></Icon>
