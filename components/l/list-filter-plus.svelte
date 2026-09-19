<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db0cu2b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db0cu2b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-filter-plus" {...props}></Icon>
