<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy5gpbcfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy5gpbcfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-0-1" {...props}></Icon>
