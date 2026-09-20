<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqhywpb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="iqhywpb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:plugins" {...props}></Icon>
