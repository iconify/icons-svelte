<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr80_bo_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gr80_bo_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hand-down" {...props}></Icon>
