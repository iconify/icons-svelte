<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejjotehzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejjotehzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-clock-outline" {...props}></Icon>
