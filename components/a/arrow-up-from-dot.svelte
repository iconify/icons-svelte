<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i61sq0mfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i61sq0mfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-from-dot" {...props}></Icon>
