<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2ebknbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ebknbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plug-connected-x" {...props}></Icon>
