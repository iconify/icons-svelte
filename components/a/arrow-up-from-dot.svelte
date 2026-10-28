<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz5gkxxdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5gkxxdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-from-dot" {...props}></Icon>
