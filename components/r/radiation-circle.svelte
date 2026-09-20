<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb47ls34d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb47ls34d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radiation-circle" {...props}></Icon>
