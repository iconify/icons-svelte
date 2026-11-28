<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhhygvs3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bhhygvs3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-plus-light" {...props}></Icon>
