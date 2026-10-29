<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqoczpb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqoczpb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:history-solid" {...props}></Icon>
