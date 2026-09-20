<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5n__acci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5n__acci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cert-manager-light" {...props}></Icon>
