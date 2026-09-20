<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4h578-1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4h578-1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-circle-outline" {...props}></Icon>
