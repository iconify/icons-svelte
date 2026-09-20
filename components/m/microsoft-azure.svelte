<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ua6lb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4ua6lb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-azure" {...props}></Icon>
