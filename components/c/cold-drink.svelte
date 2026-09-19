<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvc65utye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xvc65utye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:cold-drink" {...props}></Icon>
