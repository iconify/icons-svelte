<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulusayham.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ulusayham"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:highligt" {...props}></Icon>
