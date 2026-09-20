<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udh_yxbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udh_yxbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-move" {...props}></Icon>
