<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1b6gccuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="n1b6gccuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:drawer-left" {...props}></Icon>
