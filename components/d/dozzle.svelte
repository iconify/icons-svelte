<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaz5-_bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaz5-_bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dozzle" {...props}></Icon>
