<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4ujxob5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ujxob5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:color-helper" {...props}></Icon>
