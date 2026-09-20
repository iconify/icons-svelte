<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4wsr5byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s4wsr5byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:envira" {...props}></Icon>
