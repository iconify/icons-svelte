<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqdzkgbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdzkgbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bottle-wine" {...props}></Icon>
