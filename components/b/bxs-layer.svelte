<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zumhdobvu.css';
import '../../css/s/s26e84bqs.css';
import '../../css/x/xy5o6cs4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zumhdobvu"/><path class="s26e84bqs"/><path class="xy5o6cs4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-layer" {...props}></Icon>
