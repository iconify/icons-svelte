<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0o9jacfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0o9jacfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-minus-box" {...props}></Icon>
