<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poxyyy38h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poxyyy38h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contract-left-right-fill" {...props}></Icon>
