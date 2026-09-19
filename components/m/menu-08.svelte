<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3rvv1bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rvv1bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-08" {...props}></Icon>
