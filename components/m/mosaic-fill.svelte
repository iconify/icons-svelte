<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r91qs1n3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r91qs1n3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mosaic-fill" {...props}></Icon>
