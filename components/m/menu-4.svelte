<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nlctbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nlctbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:menu-4" {...props}></Icon>
