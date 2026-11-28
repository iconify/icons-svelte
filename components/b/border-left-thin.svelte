<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceh6ndd8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ceh6ndd8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-left-thin" {...props}></Icon>
