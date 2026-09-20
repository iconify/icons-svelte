<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l88hrmbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="l88hrmbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:replace" {...props}></Icon>
