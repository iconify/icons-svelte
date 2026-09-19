<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m902blbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m902blbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:fedex" {...props}></Icon>
