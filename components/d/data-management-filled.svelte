<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d97bulb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d97bulb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-management-filled" {...props}></Icon>
