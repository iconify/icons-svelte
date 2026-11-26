<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8vxyhb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="y8vxyhb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rectangle-horizontal" {...props}></Icon>
