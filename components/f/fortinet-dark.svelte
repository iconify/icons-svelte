<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss9riwbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss9riwbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fortinet-dark" {...props}></Icon>
