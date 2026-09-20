<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge99-vb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ge99-vb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:category" {...props}></Icon>
