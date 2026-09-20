<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7a3r-bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="n7a3r-bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:close" {...props}></Icon>
