<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_3jo0xpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e_3jo0xpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:flag-checkered" {...props}></Icon>
