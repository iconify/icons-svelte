<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rblx6mh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rblx6mh7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plug-connected" {...props}></Icon>
