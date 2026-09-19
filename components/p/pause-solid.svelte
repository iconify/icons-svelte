<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_nrh1bxn.css';
import '../../css/j/jqv_-8bsz.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<rect class="clr-i-solid clr-i-solid-path-1 q_nrh1bxn"/><rect class="clr-i-solid clr-i-solid-path-2 jqv_-8bsz"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:pause-solid" {...props}></Icon>
