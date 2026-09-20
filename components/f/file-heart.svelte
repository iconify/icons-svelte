<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtrbv7bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtrbv7bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-heart" {...props}></Icon>
