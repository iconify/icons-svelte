<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmh0rwbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmh0rwbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-drop-circle" {...props}></Icon>
