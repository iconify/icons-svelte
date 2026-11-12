<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddrnv4b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddrnv4b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceshelf-light" {...props}></Icon>
