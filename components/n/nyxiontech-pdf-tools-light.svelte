<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otjfc8b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otjfc8b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyxiontech-pdf-tools-light" {...props}></Icon>
