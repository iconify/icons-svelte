<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6l52tzsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x6l52tzsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-arrow-up-light" {...props}></Icon>
