<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnvy57b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnvy57b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-download" {...props}></Icon>
