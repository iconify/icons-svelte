<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc3yz6byc.css';
import '../../css/z/zdd0vz74c.css';
import '../../css/h/hz-xq7bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc3yz6byc"/><path class="zdd0vz74c"/><path class="hz-xq7bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:jwt" {...props}></Icon>
