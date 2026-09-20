<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cru717boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cru717boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:priority-high" {...props}></Icon>
