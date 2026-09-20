<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5hjy_sli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5hjy_sli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prunemate-light" {...props}></Icon>
