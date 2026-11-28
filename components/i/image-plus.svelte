<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycr5y2skk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycr5y2skk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-plus" {...props}></Icon>
