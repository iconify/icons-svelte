<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvr21dbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvr21dbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:emirates-airlines" {...props}></Icon>
