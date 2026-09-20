<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsw5o6x4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsw5o6x4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cam-disk-600-seg" {...props}></Icon>
