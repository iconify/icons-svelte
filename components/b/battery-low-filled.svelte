<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8w49wgny.css';
import '../../css/f/fdgucpbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8w49wgny"/><path class="fdgucpbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:battery-low-filled" {...props}></Icon>
