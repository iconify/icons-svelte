<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfhnp7yw.css';
import '../../css/c/cyhr1fblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mjfhnp7yw"/><path class="cyhr1fblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:guide" {...props}></Icon>
