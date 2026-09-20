<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6gwn9b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6gwn9b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iv-bag" {...props}></Icon>
