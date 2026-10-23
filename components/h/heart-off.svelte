<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6nhjc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6nhjc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heart-off" {...props}></Icon>
