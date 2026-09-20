<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnhjd7j_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hnhjd7j_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:package-filled" {...props}></Icon>
