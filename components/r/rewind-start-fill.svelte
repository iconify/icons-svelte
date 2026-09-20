<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i44hfh31h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i44hfh31h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-start-fill" {...props}></Icon>
