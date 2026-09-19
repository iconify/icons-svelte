<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv2zi2b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv2zi2b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-3-square-fill" {...props}></Icon>
