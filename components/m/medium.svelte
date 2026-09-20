<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7-xr7bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lu7-xr7bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:medium" {...props}></Icon>
