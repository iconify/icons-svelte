<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ind_uwmve.css';
import '../../css/y/y5z6dwezu.css';
import '../../css/g/g2lri_b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ind_uwmve"/><path class="y5z6dwezu"/><path class="g2lri_b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-keep" {...props}></Icon>
