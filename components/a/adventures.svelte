<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp1g0i7no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zp1g0i7no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:adventures" {...props}></Icon>
