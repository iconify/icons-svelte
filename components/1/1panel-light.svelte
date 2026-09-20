<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soai4mb4s.css';
import '../../css/z/zyhrf5vhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="soai4mb4s"/><path class="zyhrf5vhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:1panel-light" {...props}></Icon>
