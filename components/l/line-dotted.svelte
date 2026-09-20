<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfqk80y7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="dfqk80y7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:line-dotted" {...props}></Icon>
