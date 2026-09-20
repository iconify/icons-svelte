<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjygv35-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wjygv35-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:florist-14" {...props}></Icon>
