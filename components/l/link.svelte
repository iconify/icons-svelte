<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg4qi0d9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="zg4qi0d9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:link" {...props}></Icon>
