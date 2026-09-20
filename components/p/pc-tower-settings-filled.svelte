<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2j7vb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wz2j7vb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pc-tower-settings-filled" {...props}></Icon>
