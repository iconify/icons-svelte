<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy2i2x7fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy2i2x7fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mouse-filled" {...props}></Icon>
