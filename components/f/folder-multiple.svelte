<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg52-i0ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg52-i0ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:folder-multiple" {...props}></Icon>
