<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8vlk9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="h8vlk9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:border" {...props}></Icon>
