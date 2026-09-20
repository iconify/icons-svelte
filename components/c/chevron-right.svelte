<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a06932bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="a06932bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:chevron-right" {...props}></Icon>
