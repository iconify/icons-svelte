<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynvpeikbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynvpeikbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:octagram-shape-flat" {...props}></Icon>
