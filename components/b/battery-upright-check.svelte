<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw1umb0ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yw1umb0ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-check" {...props}></Icon>
