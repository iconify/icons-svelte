<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdb8j2bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xdb8j2bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:joomla" {...props}></Icon>
