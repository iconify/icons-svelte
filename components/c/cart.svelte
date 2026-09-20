<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk2g91wbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sk2g91wbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cart" {...props}></Icon>
