<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyfok-mpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xyfok-mpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:overflow-vertical-fill-12" {...props}></Icon>
