<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krsl0u_ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="krsl0u_ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:error" {...props}></Icon>
