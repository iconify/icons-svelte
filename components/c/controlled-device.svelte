<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2nyprbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2nyprbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:controlled-device" {...props}></Icon>
