<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe56f6bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe56f6bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:redhat" {...props}></Icon>
