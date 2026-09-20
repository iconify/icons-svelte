<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbd42eb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbd42eb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-up-line-filled" {...props}></Icon>
