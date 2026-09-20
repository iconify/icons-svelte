<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg2tnebcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mg2tnebcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coder" {...props}></Icon>
