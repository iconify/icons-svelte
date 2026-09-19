<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sab7-bbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sab7-bbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:quora" {...props}></Icon>
