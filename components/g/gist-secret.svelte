<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwp8fo_vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vwp8fo_vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:gist-secret" {...props}></Icon>
