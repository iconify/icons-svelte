<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_54cfb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_54cfb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:localess-light" {...props}></Icon>
