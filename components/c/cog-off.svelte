<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecf832bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecf832bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-off" {...props}></Icon>
