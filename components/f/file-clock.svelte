<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp9ys83uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp9ys83uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-clock" {...props}></Icon>
