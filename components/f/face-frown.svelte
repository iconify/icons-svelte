<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_oc9q1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zp_oc9q1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-frown" {...props}></Icon>
