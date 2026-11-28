<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm4px3dxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm4px3dxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bathtub" {...props}></Icon>
