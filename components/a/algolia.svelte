<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmx6jvt0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmx6jvt0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:algolia" {...props}></Icon>
