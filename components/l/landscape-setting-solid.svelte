<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1-t0lb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c1-t0lb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:landscape-setting-solid" {...props}></Icon>
