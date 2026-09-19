<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjwetpb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjwetpb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-3-square" {...props}></Icon>
