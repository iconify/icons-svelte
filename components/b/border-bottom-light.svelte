<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk738ub_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pk738ub_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-bottom-light" {...props}></Icon>
