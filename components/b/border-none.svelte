<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_8dncb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i_8dncb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-none" {...props}></Icon>
