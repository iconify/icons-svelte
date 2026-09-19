<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn7_n8brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn7_n8brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:chat" {...props}></Icon>
