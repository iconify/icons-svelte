<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dibcotb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dibcotb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:repoflow-light" {...props}></Icon>
