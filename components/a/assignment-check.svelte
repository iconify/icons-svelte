<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuhqe4wvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="iuhqe4wvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:assignment-check" {...props}></Icon>
