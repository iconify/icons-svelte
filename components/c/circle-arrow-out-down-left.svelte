<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtlns_fvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtlns_fvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-arrow-out-down-left" {...props}></Icon>
