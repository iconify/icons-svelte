<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owwit_mkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owwit_mkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:diagram-successor" {...props}></Icon>
