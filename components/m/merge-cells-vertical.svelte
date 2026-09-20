<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkaguab1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkaguab1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:merge-cells-vertical" {...props}></Icon>
