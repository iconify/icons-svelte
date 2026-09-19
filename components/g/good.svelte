<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro79hccfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ro79hccfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:good" {...props}></Icon>
