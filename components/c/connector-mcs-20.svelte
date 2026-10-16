<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnjq5zbqb.css';
import '../../css/f/f7q3gxb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dnjq5zbqb"/><path class="f7q3gxb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-mcs-20" {...props}></Icon>
