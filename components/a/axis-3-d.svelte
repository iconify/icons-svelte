<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrmmcx55c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrmmcx55c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:axis-3-d" {...props}></Icon>
