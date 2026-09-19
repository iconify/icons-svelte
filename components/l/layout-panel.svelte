<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cne_cj2pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cne_cj2pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-panel" {...props}></Icon>
