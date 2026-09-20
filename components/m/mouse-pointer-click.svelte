<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-oqkycwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-oqkycwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mouse-pointer-click" {...props}></Icon>
