<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj3e5jc6q.css';
import '../../css/c/ckm92z5cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj3e5jc6q"/><path class="ckm92z5cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:apple-solid" {...props}></Icon>
