<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykqei9bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykqei9bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator" {...props}></Icon>
