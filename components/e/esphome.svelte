<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9tsge_gb.css';
import '../../css/h/h6ao34een.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9tsge_gb"/><path class="h6ao34een"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:esphome" {...props}></Icon>
