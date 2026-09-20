<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy030ac1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hy030ac1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pulse-2-outline" {...props}></Icon>
