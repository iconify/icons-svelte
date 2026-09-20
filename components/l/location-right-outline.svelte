<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3d7eo2zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3d7eo2zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-right-outline" {...props}></Icon>
