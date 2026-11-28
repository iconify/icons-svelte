<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyogb06xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyogb06xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:keyboard-x" {...props}></Icon>
