<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe_lsrbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xe_lsrbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gnu-social" {...props}></Icon>
