<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxninwbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxninwbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dharmachakra" {...props}></Icon>
