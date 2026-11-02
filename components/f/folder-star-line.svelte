<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oms3i8bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oms3i8bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-star-line" {...props}></Icon>
