<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzmvq8bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzmvq8bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns-3" {...props}></Icon>
