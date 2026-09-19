<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp03xxb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wp03xxb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hospital" {...props}></Icon>
