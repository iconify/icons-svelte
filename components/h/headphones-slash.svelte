<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-mr8_b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x-mr8_b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:headphones-slash" {...props}></Icon>
