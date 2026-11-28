<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z379r1ssk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z379r1ssk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-star" {...props}></Icon>
