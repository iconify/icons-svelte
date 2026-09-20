<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iez2hnbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iez2hnbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:beverages-14" {...props}></Icon>
