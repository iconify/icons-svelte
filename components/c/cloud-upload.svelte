<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn54w67rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pn54w67rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-upload" {...props}></Icon>
