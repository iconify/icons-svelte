<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgrv538an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgrv538an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-lock" {...props}></Icon>
