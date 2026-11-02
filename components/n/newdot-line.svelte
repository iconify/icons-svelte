<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_6tq2bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_6tq2bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:newdot-line" {...props}></Icon>
