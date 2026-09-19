<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-j7aeb6e.css';
import '../../css/o/oy2n5ob-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-j7aeb6e"/><path class="oy2n5ob-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cloud-computing" {...props}></Icon>
