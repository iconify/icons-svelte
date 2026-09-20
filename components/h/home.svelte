<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqad6ybxx.css';
import '../../css/l/lnu_gcc9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqad6ybxx"/><path class="lnu_gcc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:home" {...props}></Icon>
