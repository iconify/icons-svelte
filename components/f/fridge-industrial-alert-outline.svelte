<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivv9obcxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivv9obcxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-industrial-alert-outline" {...props}></Icon>
