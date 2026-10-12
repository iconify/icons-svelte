<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqp8j6bvf.css';
import '../../css/m/mjdzrmbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqp8j6bvf"/><path class="mjdzrmbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flask-conical-off-filled" {...props}></Icon>
