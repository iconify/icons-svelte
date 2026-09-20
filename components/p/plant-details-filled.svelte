<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw12ul06r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uw12ul06r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-details-filled" {...props}></Icon>
