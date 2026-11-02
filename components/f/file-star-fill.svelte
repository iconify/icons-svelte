<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh46zz4eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh46zz4eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-star-fill" {...props}></Icon>
