<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsx-s2bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsx-s2bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-u-diamond-solid" {...props}></Icon>
