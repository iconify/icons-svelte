<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu5immt_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="yu5immt_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alarm-check" {...props}></Icon>
