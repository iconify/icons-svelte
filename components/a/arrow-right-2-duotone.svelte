<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf5lj2b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf5lj2b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-2-duotone" {...props}></Icon>
