<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raku_ccrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="raku_ccrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-4" {...props}></Icon>
