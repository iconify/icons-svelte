<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejxazvbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejxazvbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference-point-bottom-right" {...props}></Icon>
