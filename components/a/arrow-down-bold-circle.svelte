<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5p-wbcbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5p-wbcbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-bold-circle" {...props}></Icon>
