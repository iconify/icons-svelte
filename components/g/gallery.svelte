<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2f7h7_xh.css';
import '../../css/j/jbyel523s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2f7h7_xh"/><path clip-rule="evenodd" class="jbyel523s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:gallery" {...props}></Icon>
