<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byl-2r2kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byl-2r2kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:octagram-outline" {...props}></Icon>
