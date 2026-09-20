<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztno4swum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztno4swum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-circle-line" {...props}></Icon>
