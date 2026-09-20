<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_d2ngb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_d2ngb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-record" {...props}></Icon>
