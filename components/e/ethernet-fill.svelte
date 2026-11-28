<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_gb8j0mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i_gb8j0mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ethernet-fill" {...props}></Icon>
