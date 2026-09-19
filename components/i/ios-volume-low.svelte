<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlwegtczi.css';
import '../../css/t/t4u_3fbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rlwegtczi"/><path class="t4u_3fbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-volume-low" {...props}></Icon>
