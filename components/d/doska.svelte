<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf78fhlzv.css';
import '../../css/t/tvyzckmsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="kf78fhlzv"/><path class="tvyzckmsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:doska" {...props}></Icon>
