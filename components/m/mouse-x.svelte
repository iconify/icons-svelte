<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjdl12cwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjdl12cwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mouse-x" {...props}></Icon>
