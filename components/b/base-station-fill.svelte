<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z04b4pbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z04b4pbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:base-station-fill" {...props}></Icon>
