<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-49pk6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ck-49pk6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoice-ninja" {...props}></Icon>
