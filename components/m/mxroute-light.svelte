<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_ohccyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5_ohccyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mxroute-light" {...props}></Icon>
