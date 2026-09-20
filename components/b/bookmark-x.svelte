<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj5wg5fxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj5wg5fxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bookmark-x" {...props}></Icon>
