<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8-b8o18r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-b8o18r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:headphone" {...props}></Icon>
