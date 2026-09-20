<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr9c4dsmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr9c4dsmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:funnel-plus" {...props}></Icon>
