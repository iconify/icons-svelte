<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kueoalb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="kueoalb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:folder-star" {...props}></Icon>
