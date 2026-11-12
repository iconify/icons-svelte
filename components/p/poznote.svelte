<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyr6ptbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qyr6ptbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poznote" {...props}></Icon>
