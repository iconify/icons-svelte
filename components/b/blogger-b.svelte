<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4s9n5t8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s4s9n5t8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:blogger-b" {...props}></Icon>
