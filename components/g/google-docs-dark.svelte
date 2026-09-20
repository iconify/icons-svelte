<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxk51mbgs.css';
import '../../css/e/euu0cowqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxk51mbgs"/><path class="euu0cowqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-docs-dark" {...props}></Icon>
