<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suv_jd7bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="suv_jd7bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readarr-light" {...props}></Icon>
