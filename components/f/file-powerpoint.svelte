<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdo1a8bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo1a8bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-powerpoint" {...props}></Icon>
