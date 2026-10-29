<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccb9qpb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb9qpb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:brain-solid" {...props}></Icon>
