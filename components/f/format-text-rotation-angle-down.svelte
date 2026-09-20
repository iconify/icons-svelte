<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn340v__e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn340v__e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-rotation-angle-down" {...props}></Icon>
