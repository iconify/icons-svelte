<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7axg7sef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7axg7sef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-alert-outline" {...props}></Icon>
