<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erzf03bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bin-light" {...props}></Icon>
