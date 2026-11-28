<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smlveacnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="smlveacnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:forward-10-light" {...props}></Icon>
