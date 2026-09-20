<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt46l7bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt46l7bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:flash" {...props}></Icon>
