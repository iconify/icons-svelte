<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2g9ulz4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2g9ulz4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:help" {...props}></Icon>
