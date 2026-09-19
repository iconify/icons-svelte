<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq1x5wmte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq1x5wmte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:conference-room" {...props}></Icon>
