<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1154zb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1154zb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apps-line" {...props}></Icon>
