<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od4a2obcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od4a2obcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:baseball" {...props}></Icon>
