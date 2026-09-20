<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7f_wj1ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7f_wj1ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bazarr-light" {...props}></Icon>
