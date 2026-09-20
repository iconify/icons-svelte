<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvs_whb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvs_whb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-objects" {...props}></Icon>
