<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agkix7v6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agkix7v6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-export-outline" {...props}></Icon>
