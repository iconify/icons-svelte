<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or769vbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or769vbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:refresh-ccw" {...props}></Icon>
