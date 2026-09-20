<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cugtugbfx.css';
import '../../css/r/r-mawcbqk.css';
import '../../css/e/en4c201jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cugtugbfx"/><path class="r-mawcbqk"/><path class="en4c201jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:govi" {...props}></Icon>
