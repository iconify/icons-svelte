<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5fg72o7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p5fg72o7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-upload-filled" {...props}></Icon>
