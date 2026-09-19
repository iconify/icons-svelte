<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqfa2vbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tqfa2vbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:accessible-icon" {...props}></Icon>
