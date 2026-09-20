<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxns2fd4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxns2fd4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clipable-light" {...props}></Icon>
