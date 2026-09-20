<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjr9i_a7v.css';
import '../../css/m/m5y4f8bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="jjr9i_a7v"/><path class="m5y4f8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-intelligence-frame-line" {...props}></Icon>
