<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzb7i3bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzb7i3bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:headphone-off" {...props}></Icon>
