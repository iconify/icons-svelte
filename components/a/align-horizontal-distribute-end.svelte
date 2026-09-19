<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy_2mhbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy_2mhbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-distribute-end" {...props}></Icon>
