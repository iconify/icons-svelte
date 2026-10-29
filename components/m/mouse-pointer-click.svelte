<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr5l8bckq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr5l8bckq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer-click" {...props}></Icon>
