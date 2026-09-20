<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yztl9nsel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yztl9nsel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-5-4-filled" {...props}></Icon>
