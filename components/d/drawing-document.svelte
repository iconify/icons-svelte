<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic-4bpbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ic-4bpbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drawing-document" {...props}></Icon>
