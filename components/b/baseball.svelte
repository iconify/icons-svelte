<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcoa8gbfx.css';
import '../../css/c/cnkm8cblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcoa8gbfx"/><path class="cnkm8cblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:baseball" {...props}></Icon>
