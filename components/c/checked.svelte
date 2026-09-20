<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn87n_bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qn87n_bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:checked" {...props}></Icon>
