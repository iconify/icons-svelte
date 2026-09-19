<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0anp0nkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m0anp0nkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:developer-tools" {...props}></Icon>
