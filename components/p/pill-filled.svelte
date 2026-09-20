<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv6cmwe8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv6cmwe8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pill-filled" {...props}></Icon>
