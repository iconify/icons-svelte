<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bazxsibde.css';
import '../../css/x/xbkw3s-py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bazxsibde"/><path class="xbkw3s-py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-ccw-10-filled" {...props}></Icon>
