<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5kcp12w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hi5kcp12w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:netbox-wordmark" {...props}></Icon>
