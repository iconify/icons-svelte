<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93giq6ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="o93giq6ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:attachment" {...props}></Icon>
