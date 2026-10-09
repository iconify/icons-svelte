<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvt-qjbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cvt-qjbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-right-20" {...props}></Icon>
