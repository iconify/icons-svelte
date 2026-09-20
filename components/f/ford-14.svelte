<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkl-9wbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mkl-9wbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:ford-14" {...props}></Icon>
