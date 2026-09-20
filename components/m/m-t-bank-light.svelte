<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vawi9eb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vawi9eb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:m-t-bank-light" {...props}></Icon>
