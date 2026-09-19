<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btout9bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btout9bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:edit" {...props}></Icon>
