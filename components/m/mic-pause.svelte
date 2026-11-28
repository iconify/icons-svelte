<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om3drcbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om3drcbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mic-pause" {...props}></Icon>
