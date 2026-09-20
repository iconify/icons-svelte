<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yicezv03s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yicezv03s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-lock" {...props}></Icon>
