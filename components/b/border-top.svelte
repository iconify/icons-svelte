<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_58pwb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i_58pwb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-top" {...props}></Icon>
