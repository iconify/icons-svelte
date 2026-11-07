<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xteelq4gg.css';
import '../../css/h/h28ok-b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xteelq4gg"/><path class="h28ok-b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-from-line-bold" {...props}></Icon>
