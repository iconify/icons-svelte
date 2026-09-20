<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7fvrzbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7fvrzbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:polygon-filled" {...props}></Icon>
