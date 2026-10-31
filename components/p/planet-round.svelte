<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx-xs2vof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx-xs2vof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:planet-round" {...props}></Icon>
