<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew3ta5bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew3ta5bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pot-line" {...props}></Icon>
