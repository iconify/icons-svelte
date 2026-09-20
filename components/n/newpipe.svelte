<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik7de50zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik7de50zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:newpipe" {...props}></Icon>
