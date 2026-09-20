<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbf4n400f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbf4n400f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-cloud-2-line" {...props}></Icon>
