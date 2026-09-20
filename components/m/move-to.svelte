<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk2y--wzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="bk2y--wzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:move-to" {...props}></Icon>
