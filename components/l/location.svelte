<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtfvev2af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtfvev2af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:location" {...props}></Icon>
