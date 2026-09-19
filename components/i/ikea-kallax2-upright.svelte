<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1nr4yfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1nr4yfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-kallax2-upright" {...props}></Icon>
