<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytmj_306w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ytmj_306w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-left" {...props}></Icon>
