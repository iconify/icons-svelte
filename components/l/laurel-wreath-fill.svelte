<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1tsrb9bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1tsrb9bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laurel-wreath-fill" {...props}></Icon>
