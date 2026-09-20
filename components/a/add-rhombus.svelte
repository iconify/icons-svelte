<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvpr1296f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpr1296f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:add-rhombus" {...props}></Icon>
