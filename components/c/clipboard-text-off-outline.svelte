<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv_3ycb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv_3ycb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-off-outline" {...props}></Icon>
