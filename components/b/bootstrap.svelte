<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wijn4obnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="wijn4obnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:bootstrap" {...props}></Icon>
