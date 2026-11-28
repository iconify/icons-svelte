<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eff5a7b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="eff5a7b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-check" {...props}></Icon>
