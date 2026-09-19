<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv41ofcxd.css';
import '../../css/b/bvlph1xti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv41ofcxd"/><path class="bvlph1xti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cut" {...props}></Icon>
