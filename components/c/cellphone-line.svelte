<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbx9ybmbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbx9ybmbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cellphone-line" {...props}></Icon>
