<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9fwjzi_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m9fwjzi_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chart-area-fill" {...props}></Icon>
