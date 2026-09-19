<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjtvz0evg.css';
import '../../css/l/lzklgxbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjtvz0evg"/><path class="lzklgxbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-been-here" {...props}></Icon>
