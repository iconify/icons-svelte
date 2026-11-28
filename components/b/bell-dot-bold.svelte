<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwgtzpbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iwgtzpbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bell-dot-bold" {...props}></Icon>
