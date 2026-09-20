<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx_umsb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="yx_umsb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:remove-bug" {...props}></Icon>
