<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz31hdzhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kz31hdzhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkboxes-empty-filled" {...props}></Icon>
