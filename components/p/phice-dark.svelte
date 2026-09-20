<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doxkigb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="doxkigb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phice-dark" {...props}></Icon>
