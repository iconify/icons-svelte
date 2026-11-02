<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgrzl2o3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgrzl2o3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-x-line" {...props}></Icon>
