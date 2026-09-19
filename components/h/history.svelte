<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv064jg5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv064jg5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:history" {...props}></Icon>
