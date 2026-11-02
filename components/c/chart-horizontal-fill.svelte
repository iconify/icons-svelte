<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxr70ab7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxr70ab7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-horizontal-fill" {...props}></Icon>
