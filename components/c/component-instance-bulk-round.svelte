<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozh7-gzxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozh7-gzxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:component-instance-bulk-round" {...props}></Icon>
