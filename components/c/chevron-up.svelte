<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns9w8983n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns9w8983n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-up" {...props}></Icon>
