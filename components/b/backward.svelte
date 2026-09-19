<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbkszmbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbkszmbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:backward" {...props}></Icon>
