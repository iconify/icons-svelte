<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewb4zlb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewb4zlb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-off-filled" {...props}></Icon>
