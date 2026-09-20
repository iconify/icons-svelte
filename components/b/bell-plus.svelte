<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2k6sbbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2k6sbbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-plus" {...props}></Icon>
