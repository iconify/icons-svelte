<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq1w6hbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq1w6hbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:glasses-alt-filled" {...props}></Icon>
