<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itvzdpbdp.css';
import '../../css/z/ztsty7m5x.css';
import '../../css/j/jrpdl_7pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itvzdpbdp"/><rect class="ztsty7m5x"/><path clip-rule="evenodd" class="jrpdl_7pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-duotone" {...props}></Icon>
