<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rprcsxb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rprcsxb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:blogger" {...props}></Icon>
