<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr5o4wufh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tr5o4wufh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sleeping-in-eaved-leanto-building" {...props}></Icon>
