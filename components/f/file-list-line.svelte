<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5j3nrbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5j3nrbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-list-line" {...props}></Icon>
