<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_3_7o6we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_3_7o6we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-frame" {...props}></Icon>
