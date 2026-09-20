<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s43x5mb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s43x5mb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bold" {...props}></Icon>
